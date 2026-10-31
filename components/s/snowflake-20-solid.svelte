<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ote9-7bkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ote9-7bkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:snowflake-20-solid" {...props}></Icon>
