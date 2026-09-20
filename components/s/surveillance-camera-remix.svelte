<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kz9qcwbro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kz9qcwbro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:surveillance-camera-remix" {...props}></Icon>
