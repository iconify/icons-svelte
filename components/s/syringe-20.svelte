<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc5dhreuj.css';
import '../../css/o/oi73mpbyr.css';
import '../../css/q/qjjqbcoej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vc5dhreuj"/><path class="oi73mpbyr"/><path class="qjjqbcoej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:syringe-20" {...props}></Icon>
