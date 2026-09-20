<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sj_1dobai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sj_1dobai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:waving-flag" {...props}></Icon>
