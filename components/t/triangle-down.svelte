<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myar35bqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="myar35bqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:triangle-down" {...props}></Icon>
