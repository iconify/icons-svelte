<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awxh1dbou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="awxh1dbou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:tags" {...props}></Icon>
