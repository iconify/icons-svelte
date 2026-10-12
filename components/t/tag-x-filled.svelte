<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp6t2zbys.css';
import '../../css/l/le77-ub7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cp6t2zbys"/><path class="le77-ub7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:tag-x-filled" {...props}></Icon>
