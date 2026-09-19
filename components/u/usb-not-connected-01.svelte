<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/n/n48hqvbia.css';
import '../../css/f/f9t7w0heh.css';
import '../../css/q/qo505gp0f.css';
import '../../css/g/gvzsngngi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="n48hqvbia"/><path class="f9t7w0heh"/><path class="qo505gp0f"/><path class="gvzsngngi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:usb-not-connected-01" {...props}></Icon>
