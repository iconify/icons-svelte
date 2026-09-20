<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyte0otvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="nyte0otvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:shaver" {...props}></Icon>
