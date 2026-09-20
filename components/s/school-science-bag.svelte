<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_af56bqu.css';
import '../../css/q/qnb3e9bul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f_af56bqu"/><path class="qnb3e9bul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:school-science-bag" {...props}></Icon>
