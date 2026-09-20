<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ty-u9tbdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ty-u9tbdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:section-divider-solid" {...props}></Icon>
