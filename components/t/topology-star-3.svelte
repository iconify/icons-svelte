<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcunr6bqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bcunr6bqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:topology-star-3" {...props}></Icon>
