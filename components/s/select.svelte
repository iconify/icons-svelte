<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ut86ghblf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":44,"height":24};
const content = `<path clip-rule="evenodd" class="ut86ghblf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:select" {...props}></Icon>
