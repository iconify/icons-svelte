<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytv8j6l6t.css';
import '../../css/b/bqhst35fc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ytv8j6l6t"/><path class="bqhst35fc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:square-check" {...props}></Icon>
