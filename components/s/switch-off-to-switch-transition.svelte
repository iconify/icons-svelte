<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g36zgr.css';
import '../../css/d/dg35tf.css';
import '../../css/c/cx-from-7px.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g36zgr"/><circle class="dg35tf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:switch-off-to-switch-transition" {...props}></Icon>
