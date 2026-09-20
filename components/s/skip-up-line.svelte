<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrv1b1bij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lrv1b1bij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:skip-up-line" {...props}></Icon>
