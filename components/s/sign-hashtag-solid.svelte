<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl1m6jbwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nl1m6jbwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:sign-hashtag-solid" {...props}></Icon>
