<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j488j5z6k.css';
import '../../css/v/vbceyt5gb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j488j5z6k"/><path class="vbceyt5gb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:sport-shoe-filled" {...props}></Icon>
