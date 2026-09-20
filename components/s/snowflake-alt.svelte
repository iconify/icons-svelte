<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gg3rv6t7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gg3rv6t7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:snowflake-alt" {...props}></Icon>
