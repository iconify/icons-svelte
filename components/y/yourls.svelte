<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uq-ci9buu.css';
import '../../css/p/pg2petbgm.css';
import '../../css/e/ewxgxm6jn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uq-ci9buu"/><path class="pg2petbgm"/><path class="ewxgxm6jn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yourls" {...props}></Icon>
