<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adw7mecqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="adw7mecqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:sort-alpha-down-alt" {...props}></Icon>
