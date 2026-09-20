<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bscp3lbwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bscp3lbwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:shield-health-safety-line" {...props}></Icon>
