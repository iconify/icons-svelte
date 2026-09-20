<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkqtqp8yr.css';
import '../../css/u/uw_8mqbhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lkqtqp8yr"/><path clip-rule="evenodd" class="uw_8mqbhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:target-fill" {...props}></Icon>
