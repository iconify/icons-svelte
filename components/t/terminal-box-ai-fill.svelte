<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb2h4eb1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kb2h4eb1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:terminal-box-ai-fill" {...props}></Icon>
