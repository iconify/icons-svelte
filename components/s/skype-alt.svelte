<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au1cl9ewo.css';
import '../../css/j/j6u-38b7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="au1cl9ewo"/><path class="j6u-38b7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:skype-alt" {...props}></Icon>
