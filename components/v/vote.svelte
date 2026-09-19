<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/v/vr4lv1jdc.css';
import '../../css/x/x84ojyn9h.css';
import '../../css/p/px67vtbky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="vr4lv1jdc"/><path class="x84ojyn9h"/><path class="px67vtbky"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:vote" {...props}></Icon>
