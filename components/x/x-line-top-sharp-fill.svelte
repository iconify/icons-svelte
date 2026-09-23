<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-k3mlf4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-k3mlf4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:x-line-top-sharp-fill" {...props}></Icon>
