<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o404m-bah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o404m-bah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:users-group-fill-round" {...props}></Icon>
