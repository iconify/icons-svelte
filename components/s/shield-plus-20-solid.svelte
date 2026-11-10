<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezbwsos2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ezbwsos2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:shield-plus-20-solid" {...props}></Icon>
