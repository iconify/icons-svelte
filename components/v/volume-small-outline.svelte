<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t88j5zbtr.css';
import '../../css/l/ls3hpxbxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t88j5zbtr"/><path class="ls3hpxbxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:volume-small-outline" {...props}></Icon>
