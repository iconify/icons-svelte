<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aj-x65o5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aj-x65o5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:search-list-02" {...props}></Icon>
