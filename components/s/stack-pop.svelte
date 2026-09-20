<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcw6aj2lz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pcw6aj2lz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:stack-pop" {...props}></Icon>
