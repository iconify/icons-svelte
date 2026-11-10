<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gh3o9_kqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gh3o9_kqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:trash-arrow-up-16-solid" {...props}></Icon>
