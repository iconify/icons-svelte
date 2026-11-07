<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/u/u2j-9r34n.css';
import '../../css/p/p21ljo36x.css';
import '../../css/u/udrot0b5i.css';
import '../../css/i/i44sm08zt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="u2j-9r34n"/><path class="p21ljo36x"/><path class="udrot0b5i"/><path class="i44sm08zt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:transmission-square-linear" {...props}></Icon>
