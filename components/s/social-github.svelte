<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkkt_je4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kkkt_je4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:social-github" {...props}></Icon>
