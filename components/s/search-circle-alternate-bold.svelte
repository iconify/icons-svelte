<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf-hwtb-u.css';
import '../../css/z/z39rqtbcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tf-hwtb-u"/><path class="z39rqtbcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:search-circle-alternate-bold" {...props}></Icon>
