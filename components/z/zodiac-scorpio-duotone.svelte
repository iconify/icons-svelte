<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vto57bbdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary vto57bbdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:zodiac-scorpio-duotone" {...props}></Icon>
