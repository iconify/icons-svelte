<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jte5zrb5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jte5zrb5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:social-skype-outline" {...props}></Icon>
