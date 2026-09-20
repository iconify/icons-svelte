<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw_-m2kon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qw_-m2kon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:safari-logo-remix" {...props}></Icon>
