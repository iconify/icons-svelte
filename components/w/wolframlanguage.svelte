<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m38zlzbtp.css';
import '../../css/i/iv4nqz7tn.css';
import '../../css/f/f6g8zlbat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g transform="translate(-.009 -.001)scale(.12121)"><circle class="m38zlzbtp"/><path class="iv4nqz7tn"/><path class="f6g8zlbat"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:wolframlanguage" {...props}></Icon>
