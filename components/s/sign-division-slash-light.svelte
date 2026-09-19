<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6o_fdcnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x6o_fdcnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sign-division-slash-light" {...props}></Icon>
