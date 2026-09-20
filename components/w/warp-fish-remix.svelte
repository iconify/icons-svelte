<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpoq-6_vi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kpoq-6_vi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:warp-fish-remix" {...props}></Icon>
