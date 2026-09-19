<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzk6tjbbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="hzk6tjbbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:sun-max" {...props}></Icon>
