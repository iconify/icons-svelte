<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ea6a2ebin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ea6a2ebin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:tinyletter" {...props}></Icon>
