<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/er9vcipei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":888,"height":786};
const content = `<path class="er9vcipei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:w-upper-case" {...props}></Icon>
