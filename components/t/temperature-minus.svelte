<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqoqmd7_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eqoqmd7_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:temperature-minus" {...props}></Icon>
