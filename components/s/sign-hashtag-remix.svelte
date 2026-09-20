<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qt0me_b1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qt0me_b1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:sign-hashtag-remix" {...props}></Icon>
