<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qa1o9kgqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qa1o9kgqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:textformat-color" {...props}></Icon>
