<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fk4yqnh0p.css';
import '../../css/m/m9tv2wbji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fk4yqnh0p"/><path class="m9tv2wbji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:shopping-bag-outline" {...props}></Icon>
