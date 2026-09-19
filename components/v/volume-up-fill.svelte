<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnhzr4bxv.css';
import '../../css/s/si-8z06fj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fnhzr4bxv"/><path class="si-8z06fj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:volume-up-fill" {...props}></Icon>
