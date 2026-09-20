<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r31v6djmg.css';
import '../../css/h/h8wl53bui.css';
import '../../css/c/c7y1ahbub.css';
import '../../css/p/p-n5subdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r31v6djmg"/><path class="h8wl53bui"/><path class="c7y1ahbub"/><path class="p-n5subdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:slack-alt" {...props}></Icon>
