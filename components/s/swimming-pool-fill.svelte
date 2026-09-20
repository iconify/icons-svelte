<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5qbu8lof.css';
import '../../css/c/ca82trbjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b5qbu8lof"/><path class="ca82trbjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:swimming-pool-fill" {...props}></Icon>
