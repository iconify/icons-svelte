<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/j/jjw62pbsu.css';
import '../../css/p/pn-wogbiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="user-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="jjw62pbsu"/><path class="pn-wogbiq"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:user-outline" {...props}></Icon>
