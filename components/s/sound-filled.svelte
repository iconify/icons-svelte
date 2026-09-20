<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qldwtj9yi.css';
import '../../css/v/v8mk5pbjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qldwtj9yi"/><path class="v8mk5pbjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:sound-filled" {...props}></Icon>
