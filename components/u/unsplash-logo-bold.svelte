<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4fw52b1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z4fw52b1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:unsplash-logo-bold" {...props}></Icon>
