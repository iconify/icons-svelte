<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qt9xsy.css';
import '../../css/h/h3snei.css';
import '../../css/s/so-from-54.css';
import '../../css/f/fade-to-1.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qt9xsy"/><circle class="h3snei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:switch-off" {...props}></Icon>
