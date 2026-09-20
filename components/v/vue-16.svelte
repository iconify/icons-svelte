<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9n-sr3np.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v9n-sr3np"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:vue-16" {...props}></Icon>
