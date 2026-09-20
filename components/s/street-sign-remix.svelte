<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhf9831qg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nhf9831qg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:street-sign-remix" {...props}></Icon>
