<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ip22f7bew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ip22f7bew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:text-align-center" {...props}></Icon>
