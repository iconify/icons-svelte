<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ci7qqaciu.css';
import '../../css/a/aqsnv9bnd.css';
import '../../css/e/evw_lacsv.css';
import '../../css/p/prfptqbhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ci7qqaciu"/><path class="aqsnv9bnd"/><path class="evw_lacsv"/><path class="prfptqbhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sun-plus-20-bold" {...props}></Icon>
