<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idd3-bjtr.css';
import '../../css/i/ifbp0ub9u.css';
import '../../css/f/fp0jp3bog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="idd3-bjtr"/><path class="ifbp0ub9u"/><path class="fp0jp3bog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:run-mirror" {...props}></Icon>
