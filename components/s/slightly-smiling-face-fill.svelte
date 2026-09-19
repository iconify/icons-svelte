<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0vhp-jis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d0vhp-jis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:slightly-smiling-face-fill" {...props}></Icon>
