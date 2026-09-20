<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ab3aumb7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ab3aumb7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:trash" {...props}></Icon>
