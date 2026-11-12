<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iuq0axb2c.css';
import '../../css/u/uhazafbmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="iuq0axb2c"/><circle class="uhazafbmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:uptimerobot-dark" {...props}></Icon>
