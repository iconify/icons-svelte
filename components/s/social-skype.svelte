<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9vb0jbzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m9vb0jbzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:social-skype" {...props}></Icon>
