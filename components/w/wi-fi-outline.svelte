<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2-b-mbou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e2-b-mbou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:wi-fi-outline" {...props}></Icon>
