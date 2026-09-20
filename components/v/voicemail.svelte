<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxxb01b_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"top":-6.5};
const content = `<path class="bxxb01b_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:voicemail" {...props}></Icon>
