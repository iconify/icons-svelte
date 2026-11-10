<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bj910hkdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bj910hkdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:shield-x-mark-16-solid" {...props}></Icon>
