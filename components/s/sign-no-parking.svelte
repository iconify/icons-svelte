<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/il7qh1uhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="il7qh1uhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:sign-no-parking" {...props}></Icon>
