<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvg-fypjl.css';
import '../../css/i/i72_7ab1r.css';
import '../../css/f/feqtfmb5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yvg-fypjl"/><path class="i72_7ab1r"/><path class="feqtfmb5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:touch-id-fingerprint-square" {...props}></Icon>
