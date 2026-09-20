<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1v4pkbva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q1v4pkbva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:smiley-unhappy-bold" {...props}></Icon>
