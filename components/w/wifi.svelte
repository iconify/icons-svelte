<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrc4pogtw.css';
import '../../css/y/yof-aacxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lrc4pogtw"/><path class="yof-aacxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:wifi" {...props}></Icon>
