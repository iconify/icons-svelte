<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1_jmk1cr.css';
import '../../css/f/f3kmjcc1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="w1_jmk1cr"/><path class="f3kmjcc1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:toggle-on" {...props}></Icon>
