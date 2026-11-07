<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vskr90bqk.css';
import '../../css/k/kdjsh1b9r.css';
import '../../css/j/jlmj2df4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vskr90bqk"/><path class="kdjsh1b9r"/><path class="jlmj2df4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:skateboard-bold" {...props}></Icon>
