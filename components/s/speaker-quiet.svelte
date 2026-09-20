<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btr0sh55s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="btr0sh55s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:speaker-quiet" {...props}></Icon>
