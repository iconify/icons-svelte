<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvvegsvlw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bvvegsvlw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:topology-star-ring" {...props}></Icon>
