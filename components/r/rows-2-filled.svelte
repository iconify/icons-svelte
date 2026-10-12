<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnk0ipday.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bnk0ipday"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:rows-2-filled" {...props}></Icon>
