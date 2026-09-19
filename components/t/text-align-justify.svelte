<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo1m1lbyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bo1m1lbyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:text-align-justify" {...props}></Icon>
