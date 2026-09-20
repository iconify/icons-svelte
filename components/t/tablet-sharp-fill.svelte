<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3i5zubvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q3i5zubvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:tablet-sharp-fill" {...props}></Icon>
