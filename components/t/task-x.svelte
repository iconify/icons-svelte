<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/netr9ulfa.css';
import '../../css/k/kwu9_fbgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="netr9ulfa"/><path class="kwu9_fbgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:task-x" {...props}></Icon>
