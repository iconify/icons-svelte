<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt5jg9bzv.css';
import '../../css/e/ecruigbtp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kt5jg9bzv"/><path class="ecruigbtp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:woodwind-24" {...props}></Icon>
