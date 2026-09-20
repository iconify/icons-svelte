<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p87_qmbzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p87_qmbzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:step-forward" {...props}></Icon>
