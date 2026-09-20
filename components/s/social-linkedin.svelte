<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilecwd6xt.css';
import '../../css/t/tnupwvb0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ilecwd6xt"/><ellipse class="tnupwvb0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:social-linkedin" {...props}></Icon>
