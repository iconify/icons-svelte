<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/foed28bax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="foed28bax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:user-question" {...props}></Icon>
