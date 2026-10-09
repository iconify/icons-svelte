<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2v7xkiqi.css';
import '../../css/e/egxp91bbt.css';
import '../../css/a/agzo0q31v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t2v7xkiqi"/><path class="egxp91bbt"/><path class="agzo0q31v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-meter-20-bold" {...props}></Icon>
