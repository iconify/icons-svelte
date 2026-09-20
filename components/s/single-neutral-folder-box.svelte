<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/f/fr1i81blz.css';
import '../../css/r/rxd12t4co.css';
import '../../css/r/rcha6sbks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fr1i81blz"/><path class="rxd12t4co"/><path class="rcha6sbks"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:single-neutral-folder-box" {...props}></Icon>
