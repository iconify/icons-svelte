<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bawdxi5dr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bawdxi5dr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sign-radical" {...props}></Icon>
