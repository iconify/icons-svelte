<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qv2z8xbnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qv2z8xbnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:triangle-left-fill" {...props}></Icon>
