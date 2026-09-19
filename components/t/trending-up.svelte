<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fep7b50pi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fep7b50pi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:trending-up" {...props}></Icon>
