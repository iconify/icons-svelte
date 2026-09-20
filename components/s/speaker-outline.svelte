<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w64q5rbfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w64q5rbfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:speaker-outline" {...props}></Icon>
