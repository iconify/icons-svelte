<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-g200b_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b-g200b_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:volume-plus" {...props}></Icon>
