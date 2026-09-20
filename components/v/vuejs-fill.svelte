<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fknewjbjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fknewjbjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:vuejs-fill" {...props}></Icon>
