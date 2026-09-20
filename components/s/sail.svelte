<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_c6_8sjt.css';
import '../../css/s/s7dk4dcvy.css';
import '../../css/a/avfsq0dqv.css';
import '../../css/x/x21dsqgmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_c6_8sjt"/><path class="s7dk4dcvy"/><path class="avfsq0dqv"/><path class="x21dsqgmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:sail" {...props}></Icon>
