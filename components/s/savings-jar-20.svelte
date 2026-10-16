<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c59tb1b5l.css';
import '../../css/b/b18xgubfy.css';
import '../../css/o/onc6e2gme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c59tb1b5l"/><path class="b18xgubfy"/><path class="onc6e2gme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:savings-jar-20" {...props}></Icon>
