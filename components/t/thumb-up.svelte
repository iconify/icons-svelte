<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6dc8yq4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="v6dc8yq4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:thumb-up" {...props}></Icon>
