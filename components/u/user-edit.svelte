<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d98qsujru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d98qsujru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:user-edit" {...props}></Icon>
