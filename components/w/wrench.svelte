<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq_ralb-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eq_ralb-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:wrench" {...props}></Icon>
