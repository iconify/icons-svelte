<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5n7bgbsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w5n7bgbsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sign-lemniscate-thin" {...props}></Icon>
