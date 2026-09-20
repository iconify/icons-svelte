<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7hl1ubwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z7hl1ubwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:sonar" {...props}></Icon>
