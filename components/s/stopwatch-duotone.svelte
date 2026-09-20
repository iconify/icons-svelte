<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oom6lfvzo.css';
import '../../css/s/s1yxkv7dc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oom6lfvzo"/><path class="s1yxkv7dc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:stopwatch-duotone" {...props}></Icon>
