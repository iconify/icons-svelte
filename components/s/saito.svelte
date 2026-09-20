<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6o7oeb6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h6o7oeb6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:saito" {...props}></Icon>
