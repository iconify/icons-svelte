<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sury3b-zu.css';
import '../../css/w/w_iz3k4gm.css';
import '../../css/c/cjn1osbna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<g class="sury3b-zu"><path class="w_iz3k4gm"/><path class="cjn1osbna"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:uiua" {...props}></Icon>
