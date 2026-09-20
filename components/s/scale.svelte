<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8q3sponu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="k8q3sponu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:scale" {...props}></Icon>
