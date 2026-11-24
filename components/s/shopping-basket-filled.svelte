<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdu-cnb7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qdu-cnb7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:shopping-basket-filled" {...props}></Icon>
