<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igxg7ab5n.css';
import '../../css/n/ni2kd7y2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="igxg7ab5n"/><path class="ni2kd7y2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sunshine-light" {...props}></Icon>
