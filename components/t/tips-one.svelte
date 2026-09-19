<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv130ab-t.css';
import '../../css/y/yy7ol1bks.css';
import '../../css/a/awl6u-98m.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGxM8OJbya"><g class="hv130ab-t"><path class="yy7ol1bks"/><path class="awl6u-98m"/></g></mask></defs><path mask="url(#SVGxM8OJbya)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:tips-one" {...props}></Icon>
