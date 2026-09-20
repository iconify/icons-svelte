<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/puy3aguoq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="puy3aguoq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:trainerroad" {...props}></Icon>
