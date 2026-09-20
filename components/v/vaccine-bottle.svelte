<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2e6bqb7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k2e6bqb7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:vaccine-bottle" {...props}></Icon>
