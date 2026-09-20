<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/i/i8lcihbbn.css';
import '../../css/s/sk_l22b4b.css';
import '../../css/d/ddsr2sbfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="i8lcihbbn"/><path class="sk_l22b4b"/><path class="ddsr2sbfs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:wine" {...props}></Icon>
