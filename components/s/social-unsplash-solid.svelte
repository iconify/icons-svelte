<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fho_u-6sw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fho_u-6sw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:social-unsplash-solid" {...props}></Icon>
